<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgway08yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rgway08yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-cursor" {...props}></Icon>

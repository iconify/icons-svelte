<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm7nx75dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pm7nx75dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-move" {...props}></Icon>

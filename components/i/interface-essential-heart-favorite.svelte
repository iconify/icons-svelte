<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co7ecyb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co7ecyb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-heart-favorite" {...props}></Icon>

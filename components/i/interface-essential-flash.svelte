<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uekhz5byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uekhz5byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-flash" {...props}></Icon>

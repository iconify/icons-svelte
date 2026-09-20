<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3c-7tb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3c-7tb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-circle-2" {...props}></Icon>

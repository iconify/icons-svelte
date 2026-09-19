<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe-b2tb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oe-b2tb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:flo" {...props}></Icon>

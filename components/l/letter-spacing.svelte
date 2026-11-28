<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arta7fmsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="arta7fmsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:letter-spacing" {...props}></Icon>

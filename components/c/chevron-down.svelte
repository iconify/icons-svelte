<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpyid4bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="mpyid4bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:chevron-down" {...props}></Icon>

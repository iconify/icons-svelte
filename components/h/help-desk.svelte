<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iegve_lwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iegve_lwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:help-desk" {...props}></Icon>

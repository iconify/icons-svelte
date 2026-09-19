<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxuo-fmrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sxuo-fmrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:r-circle-fill" {...props}></Icon>

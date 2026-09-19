<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0coq4_wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n0coq4_wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:gear-wide-connected" {...props}></Icon>

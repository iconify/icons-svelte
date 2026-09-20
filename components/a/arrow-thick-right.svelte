<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rumij6bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rumij6bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thick-right" {...props}></Icon>

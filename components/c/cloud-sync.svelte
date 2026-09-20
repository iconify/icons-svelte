<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg6pjbb_x.css';
import '../../css/l/l70ob6bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pg6pjbb_x"/><path class="l70ob6bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-sync" {...props}></Icon>

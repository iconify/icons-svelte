<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfoeq1bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bfoeq1bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:record-fill" {...props}></Icon>

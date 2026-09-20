<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf6u91bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pf6u91bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-up-left" {...props}></Icon>

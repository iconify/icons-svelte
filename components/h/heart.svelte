<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgqwb1bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqwb1bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:heart" {...props}></Icon>

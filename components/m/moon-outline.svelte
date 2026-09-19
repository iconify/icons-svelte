<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcpwg3bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcpwg3bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:moon-outline" {...props}></Icon>

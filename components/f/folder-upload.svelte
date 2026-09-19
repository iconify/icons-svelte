<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhjyh2bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhjyh2bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:folder-upload" {...props}></Icon>

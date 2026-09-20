<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbjnk2bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbjnk2bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-74-small" {...props}></Icon>

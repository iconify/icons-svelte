<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yedc29b5u.css';
import '../../css/x/xdemm2bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yedc29b5u"/><path class="xdemm2bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:power-fill" {...props}></Icon>

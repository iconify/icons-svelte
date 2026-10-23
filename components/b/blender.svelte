<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj3d1zxsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj3d1zxsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:blender" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frx5_9vue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frx5_9vue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:file-delete" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pge1vjbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pge1vjbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:copy-x-sharp" {...props}></Icon>

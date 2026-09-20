<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pta4jsbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pta4jsbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:facebook" {...props}></Icon>

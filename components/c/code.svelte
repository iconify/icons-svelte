<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeialtbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeialtbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:code" {...props}></Icon>

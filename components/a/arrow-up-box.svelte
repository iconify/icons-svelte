<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbxl4wb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbxl4wb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-up-box" {...props}></Icon>

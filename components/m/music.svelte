<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zamm2dodg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zamm2dodg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:music" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woa1r2bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woa1r2bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-arrow-right" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fld1fknfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fld1fknfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:home" {...props}></Icon>

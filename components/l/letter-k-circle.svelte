<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzel1db5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzel1db5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-k-circle" {...props}></Icon>

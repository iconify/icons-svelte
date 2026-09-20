<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik1ry9vnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik1ry9vnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-o" {...props}></Icon>

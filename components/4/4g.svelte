<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp-kso11r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp-kso11r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:4g" {...props}></Icon>

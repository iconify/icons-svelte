<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf8ewmb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf8ewmb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:percent" {...props}></Icon>

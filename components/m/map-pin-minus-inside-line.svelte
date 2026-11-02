<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ej_g2mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ej_g2mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-minus-inside-line" {...props}></Icon>

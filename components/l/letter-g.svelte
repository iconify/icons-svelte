<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxyc8_-xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxyc8_-xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-g" {...props}></Icon>

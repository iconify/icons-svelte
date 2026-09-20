<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs5sg8uyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs5sg8uyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-q-circle" {...props}></Icon>

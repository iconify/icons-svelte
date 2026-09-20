<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm_p9eb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_p9eb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-d-circle" {...props}></Icon>

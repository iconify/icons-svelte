<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzq-v8b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzq-v8b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-n" {...props}></Icon>

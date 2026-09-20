<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd3phbbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd3phbbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-distribute-center" {...props}></Icon>

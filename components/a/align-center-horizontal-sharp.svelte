<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eef3-vfsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eef3-vfsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-center-horizontal-sharp" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72nufbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i72nufbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-distribute-end-sharp" {...props}></Icon>

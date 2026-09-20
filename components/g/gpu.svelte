<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccavtebww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccavtebww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gpu" {...props}></Icon>

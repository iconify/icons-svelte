<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej63n7c8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej63n7c8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:radio-handheld" {...props}></Icon>

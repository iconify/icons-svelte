<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a--qirb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a--qirb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:keyboard-glyph" {...props}></Icon>

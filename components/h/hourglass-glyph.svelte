<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atmwxtv7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atmwxtv7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:hourglass-glyph" {...props}></Icon>

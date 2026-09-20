<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i63tbkbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i63tbkbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:braces-content" {...props}></Icon>

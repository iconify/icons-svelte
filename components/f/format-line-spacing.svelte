<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irq17xbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="irq17xbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-line-spacing" {...props}></Icon>

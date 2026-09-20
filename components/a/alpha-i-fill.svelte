<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0xrnioja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y0xrnioja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-i-fill" {...props}></Icon>

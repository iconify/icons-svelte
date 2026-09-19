<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng5ph0tfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ng5ph0tfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map" {...props}></Icon>

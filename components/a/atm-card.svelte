<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv2svbc7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="wv2svbc7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:atm-card" {...props}></Icon>

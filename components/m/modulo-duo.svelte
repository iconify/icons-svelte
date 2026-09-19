<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swiw1cbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="swiw1cbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:modulo-duo" {...props}></Icon>

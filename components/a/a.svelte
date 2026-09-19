<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siey_tgax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="siey_tgax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:a" {...props}></Icon>

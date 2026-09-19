<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by65-jbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="by65-jbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:helicopter" {...props}></Icon>

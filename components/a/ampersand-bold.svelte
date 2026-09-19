<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2pai4fwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="n2pai4fwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ampersand-bold" {...props}></Icon>

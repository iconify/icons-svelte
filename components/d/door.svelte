<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vva03ib8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vva03ib8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:door" {...props}></Icon>

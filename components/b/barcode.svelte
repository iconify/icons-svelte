<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv3kr87mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bv3kr87mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:barcode" {...props}></Icon>

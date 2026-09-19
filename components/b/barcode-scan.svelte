<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-asay8ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="u-asay8ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:barcode-scan" {...props}></Icon>

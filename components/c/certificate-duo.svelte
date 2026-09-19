<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr11d0b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qr11d0b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:certificate-duo" {...props}></Icon>

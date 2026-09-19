<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/invwfrbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="invwfrbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:barcode" {...props}></Icon>

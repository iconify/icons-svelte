<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbrp9spkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sbrp9spkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:paypal" {...props}></Icon>

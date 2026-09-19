<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsuvst8qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="dsuvst8qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:m-bold" {...props}></Icon>

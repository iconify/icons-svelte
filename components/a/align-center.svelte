<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw4dz4bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sw4dz4bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-center" {...props}></Icon>

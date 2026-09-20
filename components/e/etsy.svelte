<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr6tjj6uj.css';
import '../../css/p/pytza4zbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dr6tjj6uj"/><path class="pytza4zbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etsy" {...props}></Icon>

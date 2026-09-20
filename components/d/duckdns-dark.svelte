<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxhh4rbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxhh4rbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duckdns-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_vjcckt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yr_vjcckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jwt-io-light" {...props}></Icon>

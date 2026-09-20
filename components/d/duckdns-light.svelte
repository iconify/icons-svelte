<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozh_-hb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozh_-hb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duckdns-light" {...props}></Icon>

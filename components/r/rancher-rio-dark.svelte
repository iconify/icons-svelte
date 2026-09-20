<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edrt2xbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edrt2xbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-rio-dark" {...props}></Icon>

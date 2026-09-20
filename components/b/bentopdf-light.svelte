<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5my2xbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u5my2xbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bentopdf-light" {...props}></Icon>

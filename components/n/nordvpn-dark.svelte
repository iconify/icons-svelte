<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csz2z-byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csz2z-byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nordvpn-dark" {...props}></Icon>

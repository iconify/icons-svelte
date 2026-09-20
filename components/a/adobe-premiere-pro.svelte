<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhaq2tbcu.css';
import '../../css/n/n1prgobsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhaq2tbcu"/><path class="n1prgobsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-premiere-pro" {...props}></Icon>

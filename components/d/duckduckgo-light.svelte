<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypknmkbto.css';
import '../../css/g/g1k_hynjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypknmkbto"/><path class="g1k_hynjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:duckduckgo-light" {...props}></Icon>

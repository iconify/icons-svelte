<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip2z-kb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ip2z-kb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nvidia" {...props}></Icon>

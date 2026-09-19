<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmti67w2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pmti67w2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:download-stroke-12" {...props}></Icon>

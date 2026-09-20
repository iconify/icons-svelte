<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yolrx-bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yolrx-bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-gemini-light" {...props}></Icon>

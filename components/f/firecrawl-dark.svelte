<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_k_5gja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za_k_5gja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firecrawl-dark" {...props}></Icon>

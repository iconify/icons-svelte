<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u767w3b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u767w3b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-chrome-dark" {...props}></Icon>

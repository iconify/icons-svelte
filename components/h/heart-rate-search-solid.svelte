<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbytlgm_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fbytlgm_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heart-rate-search-solid" {...props}></Icon>

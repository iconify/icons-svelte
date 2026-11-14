<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufa1labba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufa1labba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ollama-light" {...props}></Icon>

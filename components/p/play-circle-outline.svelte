<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwlmahb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="cwlmahb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:play-circle-outline" {...props}></Icon>

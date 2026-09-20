<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5v1u61ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5v1u61ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad24a10fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ad24a10fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haven-dark" {...props}></Icon>

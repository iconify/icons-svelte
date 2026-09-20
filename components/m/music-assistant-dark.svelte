<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isqzje__y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isqzje__y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:music-assistant-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfy8vzb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfy8vzb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firebase-dark" {...props}></Icon>

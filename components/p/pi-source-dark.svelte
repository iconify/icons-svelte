<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_b39fb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_b39fb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-source-dark" {...props}></Icon>

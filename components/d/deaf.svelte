<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_p894yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nf_p894yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:deaf" {...props}></Icon>

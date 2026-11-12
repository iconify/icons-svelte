<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddcs7acfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddcs7acfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alpine-linux-dark" {...props}></Icon>

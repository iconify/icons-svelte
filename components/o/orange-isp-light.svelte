<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q262y9b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q262y9b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orange-isp-light" {...props}></Icon>

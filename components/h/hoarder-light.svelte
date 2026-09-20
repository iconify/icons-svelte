<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh1qadn_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xh1qadn_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hoarder-light" {...props}></Icon>

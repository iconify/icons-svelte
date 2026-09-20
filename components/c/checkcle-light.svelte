<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5_g_lbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5_g_lbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkcle-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1arryb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1arryb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulse-dark" {...props}></Icon>

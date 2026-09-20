<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw402bc7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw402bc7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opencut-light" {...props}></Icon>

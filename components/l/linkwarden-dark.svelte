<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe2dzfbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qe2dzfbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkwarden-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegwdd90q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oegwdd90q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glitchtip-light" {...props}></Icon>

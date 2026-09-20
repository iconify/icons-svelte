<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lldu6nt-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lldu6nt-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orb-light" {...props}></Icon>

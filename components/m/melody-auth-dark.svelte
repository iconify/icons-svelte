<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqppkb4wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqppkb4wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:melody-auth-dark" {...props}></Icon>

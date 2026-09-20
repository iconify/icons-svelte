<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rean51pzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rean51pzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-light" {...props}></Icon>

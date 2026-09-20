<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzuu6qb5w.css';
import '../../css/z/zjgo95xol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzuu6qb5w"/><path class="zjgo95xol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pico-pixel-player" {...props}></Icon>

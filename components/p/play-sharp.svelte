<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw432ybht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lw432ybht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-sharp" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzdm7fsxu.css';
import '../../css/l/lw4h2zb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzdm7fsxu"/><path class="lw4h2zb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:push-outline" {...props}></Icon>

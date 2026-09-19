<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh0qs-btc.css';
import '../../css/d/dgnjy1a4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="lh0qs-btc"/><path class="dgnjy1a4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:easel-outline" {...props}></Icon>

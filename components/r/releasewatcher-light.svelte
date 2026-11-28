<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqrll5btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqrll5btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:releasewatcher-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc1wr8bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc1wr8bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fubotv-light" {...props}></Icon>

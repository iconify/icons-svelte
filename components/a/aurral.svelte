<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbfx2ibbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbfx2ibbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aurral" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ep5t2cq.css';
import '../../css/b/btg1i0bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2ep5t2cq"/><path class="btg1i0bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-dreamweaver" {...props}></Icon>

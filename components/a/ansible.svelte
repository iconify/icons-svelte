<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncxf18bye.css';
import '../../css/l/ld7aedbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncxf18bye"/><path class="ld7aedbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ansible" {...props}></Icon>

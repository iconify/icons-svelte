<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0x_n6utq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p0x_n6utq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-ankh" {...props}></Icon>

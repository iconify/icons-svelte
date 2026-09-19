<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn1vx7i1f.css';
import '../../css/b/bfpgpzbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn1vx7i1f"/><path class="bfpgpzbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bookmarks" {...props}></Icon>

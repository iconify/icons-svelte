<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibe_u-t6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="ibe_u-t6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6yn4_bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":432};
const content = `<path class="b6yn4_bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:battery-charging" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2-tg4hoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":432};
const content = `<path class="v2-tg4hoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:facebook" {...props}></Icon>

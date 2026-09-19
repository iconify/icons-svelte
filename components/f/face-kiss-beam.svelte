<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luzm4jb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="luzm4jb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-kiss-beam" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2a-lbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="db2a-lbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-kiss-wink-heart" {...props}></Icon>

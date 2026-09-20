<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmkn8zbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xmkn8zbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:move-outline" {...props}></Icon>

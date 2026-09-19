<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbh18kjzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbh18kjzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-star" {...props}></Icon>

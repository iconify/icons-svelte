<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw-wd3gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrw-wd3gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-laptop" {...props}></Icon>

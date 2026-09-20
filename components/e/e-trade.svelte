<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zykmcsy6u.css';
import '../../css/c/cf4rmeasd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zykmcsy6u"/><path class="cf4rmeasd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:e-trade" {...props}></Icon>

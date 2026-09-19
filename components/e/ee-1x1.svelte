<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdia6fa5z.css';
import '../../css/q/q2l4humxv.css';
import '../../css/m/me0wbo9yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdia6fa5z"/><path class="q2l4humxv"/><path class="me0wbo9yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ee-1x1" {...props}></Icon>

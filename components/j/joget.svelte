<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb0p2xp2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="zb0p2xp2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:joget" {...props}></Icon>

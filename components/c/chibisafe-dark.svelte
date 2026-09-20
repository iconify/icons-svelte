<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teznrsbms.css';
import '../../css/y/ypvg3cc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="teznrsbms"/><path class="ypvg3cc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chibisafe-dark" {...props}></Icon>

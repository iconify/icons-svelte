<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noq7sdh0f.css';
import '../../css/e/earracbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="noq7sdh0f"/><path class="earracbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:handshake-20-bold" {...props}></Icon>

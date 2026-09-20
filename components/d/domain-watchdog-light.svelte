<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1_i3l3vn.css';
import '../../css/m/m5lp6jbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="g1_i3l3vn"/><path class="m5lp6jbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-watchdog-light" {...props}></Icon>

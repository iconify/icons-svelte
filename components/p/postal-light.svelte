<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdblbht-m.css';
import '../../css/t/tdt6iwb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdblbht-m"/><path class="tdt6iwb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postal-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvr1cwbqh.css';
import '../../css/q/qfa9e5rcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvr1cwbqh"/><path class="qfa9e5rcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-48-bold" {...props}></Icon>

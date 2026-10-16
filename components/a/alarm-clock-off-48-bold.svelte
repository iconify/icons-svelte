<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2k8ah5hs.css';
import '../../css/q/q18-obcpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d2k8ah5hs"/><path class="q18-obcpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-off-48-bold" {...props}></Icon>

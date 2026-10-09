<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfspippzt.css';
import '../../css/q/qkvjsbbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfspippzt"/><path class="qkvjsbbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-nut-48-bold" {...props}></Icon>

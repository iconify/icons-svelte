<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df474cc-n.css';
import '../../css/y/yxgyrcb-d.css';
import '../../css/r/rkg9se97n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="df474cc-n"/><path class="yxgyrcb-d"/><path class="rkg9se97n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-meter-48-bold" {...props}></Icon>

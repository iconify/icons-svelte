<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yry6u38_x.css';
import '../../css/v/vci34obyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yry6u38_x"/><path class="vci34obyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docking-station" {...props}></Icon>

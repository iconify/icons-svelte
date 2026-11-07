<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yivcorr_n.css';
import '../../css/v/vz52zxbce.css';
import '../../css/q/qruphy0vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yivcorr_n"/><path class="vz52zxbce"/><path class="qruphy0vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-camera-bold" {...props}></Icon>

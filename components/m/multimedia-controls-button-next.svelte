<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz45orb-l.css';
import '../../css/p/pd3uy56kd.css';
import '../../css/y/yhzwzc4av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz45orb-l"/><path class="pd3uy56kd"/><path class="yhzwzc4av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:multimedia-controls-button-next" {...props}></Icon>

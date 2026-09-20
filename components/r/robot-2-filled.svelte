<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmecbubtg.css';
import '../../css/q/qqeg1x_1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmecbubtg"/><path class="qqeg1x_1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:robot-2-filled" {...props}></Icon>

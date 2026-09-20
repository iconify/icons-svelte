<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmc1m3ixj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmc1m3ixj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gamepad-2" {...props}></Icon>

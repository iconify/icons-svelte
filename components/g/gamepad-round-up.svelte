<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta501bc4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta501bc4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-round-up" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/synvtgbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="synvtgbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:autopilot-car-1-bold" {...props}></Icon>

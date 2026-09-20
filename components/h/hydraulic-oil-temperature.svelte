<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-q_h0b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-q_h0b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hydraulic-oil-temperature" {...props}></Icon>

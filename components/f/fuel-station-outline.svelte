<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzk4g4ahp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzk4g4ahp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fuel-station-outline" {...props}></Icon>

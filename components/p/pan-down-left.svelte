<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w51dps7dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w51dps7dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pan-down-left" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-u15bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0-u15bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:parachute-outline" {...props}></Icon>

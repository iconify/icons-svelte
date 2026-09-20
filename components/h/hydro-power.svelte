<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpy3xnbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpy3xnbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hydro-power" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlo555byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlo555byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:homey" {...props}></Icon>

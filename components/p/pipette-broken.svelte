<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/murvr1lpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="murvr1lpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pipette-broken" {...props}></Icon>

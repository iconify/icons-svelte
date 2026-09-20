<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwh1grb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh1grb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-open-play-outline" {...props}></Icon>

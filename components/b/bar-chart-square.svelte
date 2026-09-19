<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd3nyb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd3nyb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bar-chart-square" {...props}></Icon>

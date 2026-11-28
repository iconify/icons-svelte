<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkt0p6bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkt0p6bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gauge-check" {...props}></Icon>

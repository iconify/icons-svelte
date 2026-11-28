<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sas_macef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sas_macef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cassette-play" {...props}></Icon>

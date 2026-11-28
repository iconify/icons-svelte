<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwxet59ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwxet59ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clapperboard-check" {...props}></Icon>

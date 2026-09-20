<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fju0sum8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fju0sum8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:codepen-line" {...props}></Icon>

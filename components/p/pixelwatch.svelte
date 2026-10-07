<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz1bbrbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz1bbrbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pixelwatch" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzj21sb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzj21sb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-starts-with" {...props}></Icon>

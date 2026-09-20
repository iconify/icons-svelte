<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im8el_gaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im8el_gaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chrome-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvw_2eb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvw_2eb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-podcast" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt8y22vno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt8y22vno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-assistant" {...props}></Icon>

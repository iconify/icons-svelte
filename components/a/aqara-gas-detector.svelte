<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clg293vdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clg293vdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-gas-detector" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xug077bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xug077bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulbs" {...props}></Icon>

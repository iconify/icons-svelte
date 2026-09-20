<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvlvdy-0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvlvdy-0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-rhombus-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i67zw_bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i67zw_bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:internet-archive" {...props}></Icon>

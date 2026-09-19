<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc1uw4bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc1uw4bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:directions" {...props}></Icon>

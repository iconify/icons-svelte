<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on7ukn-zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on7ukn-zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netbird" {...props}></Icon>

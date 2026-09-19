<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wipyugbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wipyugbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-empty" {...props}></Icon>

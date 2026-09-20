<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl_5fob-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wl_5fob-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mounted-slotted-dispenser-with-dog-wearing-collar" {...props}></Icon>

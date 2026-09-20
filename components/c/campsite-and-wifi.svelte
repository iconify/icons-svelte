<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8mc_4l0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g8mc_4l0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-and-wifi" {...props}></Icon>

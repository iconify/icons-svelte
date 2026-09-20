<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5dad0fgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g5dad0fgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jp-fire-station" {...props}></Icon>

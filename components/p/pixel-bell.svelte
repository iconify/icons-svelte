<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr5dvv4wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jr5dvv4wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-bell" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3bt70wlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d3bt70wlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-paper" {...props}></Icon>

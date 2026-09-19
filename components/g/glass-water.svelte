<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh6orpnrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hh6orpnrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:glass-water" {...props}></Icon>

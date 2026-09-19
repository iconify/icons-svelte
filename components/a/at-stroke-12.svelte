<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn_x731ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zn_x731ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-stroke-12" {...props}></Icon>

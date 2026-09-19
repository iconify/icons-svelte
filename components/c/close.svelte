<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osi2d3_5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osi2d3_5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:close" {...props}></Icon>

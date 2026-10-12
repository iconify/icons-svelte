<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz11l89yb.css';
import '../../css/o/oimt4ji_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uz11l89yb"/><path class="oimt4ji_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-arrow-right-stroke-20" {...props}></Icon>

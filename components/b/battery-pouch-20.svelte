<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb2bgubhg.css';
import '../../css/i/iat97dbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zb2bgubhg"/><path class="iat97dbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pouch-20" {...props}></Icon>

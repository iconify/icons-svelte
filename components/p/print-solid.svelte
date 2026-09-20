<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry68nbwkv.css';
import '../../css/b/b09d1x-lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ry68nbwkv"/><path class="b09d1x-lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:print-solid" {...props}></Icon>

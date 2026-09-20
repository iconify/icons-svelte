<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztgw17b4p.css';
import '../../css/l/laiy7fbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ztgw17b4p"/><path class="laiy7fbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:chart-increasing-with-yen" {...props}></Icon>

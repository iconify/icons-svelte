<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuuuxzbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuuuxzbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:disc-solid" {...props}></Icon>

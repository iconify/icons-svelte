<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbdu_8b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":416};
const content = `<path class="rbdu_8b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:blur-off" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5dfkkbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="w5dfkkbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heart-stroke-12" {...props}></Icon>

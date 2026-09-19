<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc4r43bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kc4r43bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:italic-stroke-12" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq9548qes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cq9548qes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-a" {...props}></Icon>

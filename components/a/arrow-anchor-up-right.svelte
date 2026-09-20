<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbd_-abaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbd_-abaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-anchor-up-right" {...props}></Icon>

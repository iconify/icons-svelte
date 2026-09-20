<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wewv2-b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wewv2-b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:chevron-up" {...props}></Icon>

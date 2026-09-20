<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt7-9wjst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bt7-9wjst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:arrow-anchor-up-left" {...props}></Icon>

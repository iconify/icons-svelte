<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f--7-bb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="f--7-bb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:funnel-dollar" {...props}></Icon>

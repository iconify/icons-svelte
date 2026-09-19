<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsidy9_gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lsidy9_gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:circle-pause" {...props}></Icon>

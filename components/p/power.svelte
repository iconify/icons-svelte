<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh_3glbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nh_3glbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:power" {...props}></Icon>

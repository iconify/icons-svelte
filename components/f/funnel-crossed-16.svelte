<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-x1t1gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i3-x1t1gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:funnel-crossed-16" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlx2_7l6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wlx2_7l6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mouse" {...props}></Icon>

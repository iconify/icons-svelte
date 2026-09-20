<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02zmjtek.css';
import '../../css/x/xk9upfb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h02zmjtek"/><path class="xk9upfb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:download" {...props}></Icon>

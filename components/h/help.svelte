<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp5rt_4bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dp5rt_4bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:help" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn08rb2an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xn08rb2an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canoe-above-water" {...props}></Icon>

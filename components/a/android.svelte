<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_a9fclgc.css';
import '../../css/b/blj5kcbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":150};
const content = `<path class="l_a9fclgc"/><path class="blj5kcbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:android" {...props}></Icon>

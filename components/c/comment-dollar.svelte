<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yly7_1ytk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yly7_1ytk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment-dollar" {...props}></Icon>

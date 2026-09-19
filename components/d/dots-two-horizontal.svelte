<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a77l2yh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a77l2yh7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:dots-two-horizontal" {...props}></Icon>

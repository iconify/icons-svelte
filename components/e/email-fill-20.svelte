<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtwmiac1q.css';
import '../../css/r/re_226bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rtwmiac1q"/><path class="re_226bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:email-fill-20" {...props}></Icon>

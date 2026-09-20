<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkum7r7xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rkum7r7xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:heart" {...props}></Icon>

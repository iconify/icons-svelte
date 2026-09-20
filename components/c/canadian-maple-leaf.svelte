<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejor03bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejor03bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:canadian-maple-leaf" {...props}></Icon>

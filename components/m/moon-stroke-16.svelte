<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgi1i3bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cgi1i3bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moon-stroke-16" {...props}></Icon>

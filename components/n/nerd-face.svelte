<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn_x48p1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vn_x48p1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:nerd-face" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgfnc9rkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wgfnc9rkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:directions-sign" {...props}></Icon>

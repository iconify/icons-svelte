<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2civt24x.css';
import '../../css/v/vbo9mcctp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p2civt24x"/><path class="vbo9mcctp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-respiratory" {...props}></Icon>

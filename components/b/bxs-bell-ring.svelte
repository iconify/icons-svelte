<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzx88bb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzx88bb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bell-ring" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybue2s69d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ybue2s69d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-frown" {...props}></Icon>

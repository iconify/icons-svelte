<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr399-bdh.css';
import '../../css/i/in-984b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="zr399-bdh"/><path class="in-984b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:briefcase-outline" {...props}></Icon>

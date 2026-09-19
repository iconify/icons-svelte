<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu0yxyb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":512};
const content = `<path class="vu0yxyb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:imgbot" {...props}></Icon>

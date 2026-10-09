<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thsmnl_1a.css';
import '../../css/h/hspx3ob0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thsmnl_1a"/><path class="hspx3ob0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bowling-48-bold" {...props}></Icon>

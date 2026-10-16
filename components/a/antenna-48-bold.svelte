<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4w681bdr.css';
import '../../css/j/j-f5_l35o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z4w681bdr"/><path class="j-f5_l35o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:antenna-48-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsi3rkp0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nsi3rkp0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-click-20-bold" {...props}></Icon>

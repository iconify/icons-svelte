<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0r8abuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vh0r8abuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-horizontal-20" {...props}></Icon>

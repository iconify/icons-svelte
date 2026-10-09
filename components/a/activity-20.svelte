<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpjz6abop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cpjz6abop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:activity-20" {...props}></Icon>

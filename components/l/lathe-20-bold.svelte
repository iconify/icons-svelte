<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7d4ky4we.css';
import '../../css/p/polb77bwu.css';
import '../../css/s/sorlblovj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c7d4ky4we"/><path class="polb77bwu"/><path class="sorlblovj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lathe-20-bold" {...props}></Icon>

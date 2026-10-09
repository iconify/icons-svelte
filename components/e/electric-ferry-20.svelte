<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry_fo9lxv.css';
import '../../css/x/x7suexyet.css';
import '../../css/e/eeqn6pbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ry_fo9lxv"/><path class="x7suexyet"/><path class="eeqn6pbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-ferry-20" {...props}></Icon>

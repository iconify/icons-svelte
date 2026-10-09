<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iur812moa.css';
import '../../css/y/y40w3sucp.css';
import '../../css/o/o6x3htbqm.css';
import '../../css/r/rzkosvb-d.css';
import '../../css/z/zkili02bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iur812moa"/><path class="y40w3sucp"/><path class="o6x3htbqm"/><path class="rzkosvb-d"/><path class="zkili02bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-solar-20-bold" {...props}></Icon>

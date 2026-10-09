<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfzmnvd-w.css';
import '../../css/y/yo9tbkbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lfzmnvd-w"/><path class="yo9tbkbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-20" {...props}></Icon>

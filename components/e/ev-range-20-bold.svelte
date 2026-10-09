<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekbu-fbrm.css';
import '../../css/x/x_ur3irsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ekbu-fbrm"/><path class="x_ur3irsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-range-20-bold" {...props}></Icon>

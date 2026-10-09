<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0gjrpb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r0gjrpb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:command-20-bold" {...props}></Icon>

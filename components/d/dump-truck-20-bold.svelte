<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkgj9ib4r.css';
import '../../css/x/x1b3r-bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bkgj9ib4r"/><path class="x1b3r-bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dump-truck-20-bold" {...props}></Icon>

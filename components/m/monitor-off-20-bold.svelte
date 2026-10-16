<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lznpb-b-w.css';
import '../../css/w/w0poz4bns.css';
import '../../css/n/n4zx3qb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lznpb-b-w"/><path class="w0poz4bns"/><path class="n4zx3qb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-off-20-bold" {...props}></Icon>

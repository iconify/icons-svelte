<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9gesab3q.css';
import '../../css/q/qbvrdcndr.css';
import '../../css/e/ebvsrm49p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9gesab3q"/><path class="qbvrdcndr"/><path class="ebvsrm49p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-cable-20" {...props}></Icon>

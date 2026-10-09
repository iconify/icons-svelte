<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aww2hc3xd.css';
import '../../css/d/d3halac9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aww2hc3xd"/><path class="d3halac9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-type2-20-bold" {...props}></Icon>

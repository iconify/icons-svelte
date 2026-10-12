<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2zh3obzl.css';
import '../../css/u/upem778kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e2zh3obzl"/><path class="upem778kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-pulse-20" {...props}></Icon>

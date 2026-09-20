<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2jl40bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r2jl40bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-dashboards" {...props}></Icon>

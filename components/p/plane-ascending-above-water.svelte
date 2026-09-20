<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr32j03ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dr32j03ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-ascending-above-water" {...props}></Icon>

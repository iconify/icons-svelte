<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aazg57bwd.css';
import '../../css/r/r0x1nqbvh.css';
import '../../css/a/asc4-fm2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aazg57bwd"/><path class="r0x1nqbvh"/><path class="asc4-fm2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-check-20-bold" {...props}></Icon>

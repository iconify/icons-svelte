<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umpd97b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umpd97b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:footsteps-sharp" {...props}></Icon>

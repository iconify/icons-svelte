<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0gw__81g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0gw__81g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:animal" {...props}></Icon>

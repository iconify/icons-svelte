<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8lutftsu.css';
import '../../css/o/oz-ecrdze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8lutftsu"/><path class="oz-ecrdze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghidra-dark" {...props}></Icon>

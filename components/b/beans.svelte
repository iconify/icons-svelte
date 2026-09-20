<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3d2xsbfa.css';
import '../../css/o/o2zoxdw1l.css';
import '../../css/s/sqkqqys5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="v3d2xsbfa"/><path class="o2zoxdw1l"/><path class="sqkqqys5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:beans" {...props}></Icon>

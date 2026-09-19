<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abx036wst.css';
import '../../css/n/nv2jz3bhl.css';
import '../../css/l/l3pzy9htd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abx036wst"/><path class="nv2jz3bhl"/><path class="l3pzy9htd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-car" {...props}></Icon>

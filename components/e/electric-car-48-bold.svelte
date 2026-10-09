<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re49p_baz.css';
import '../../css/s/sxankrbtm.css';
import '../../css/u/up5n2bcfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="re49p_baz"/><path class="sxankrbtm"/><path class="up5n2bcfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-48-bold" {...props}></Icon>

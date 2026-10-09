<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re49p_baz.css';
import '../../css/s/sxankrbtm.css';
import '../../css/x/xcrynda4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="re49p_baz"/><path class="sxankrbtm"/><path class="xcrynda4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-in-hybrid-48-bold" {...props}></Icon>

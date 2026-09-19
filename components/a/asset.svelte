<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhv6agb1d.css';
import '../../css/o/oqcudtb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bhv6agb1d"/><path class="oqcudtb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:asset" {...props}></Icon>

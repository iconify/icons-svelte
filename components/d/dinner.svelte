<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh25mva7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mh25mva7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:dinner" {...props}></Icon>

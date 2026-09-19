<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnsjc_z3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="rnsjc_z3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-2" {...props}></Icon>

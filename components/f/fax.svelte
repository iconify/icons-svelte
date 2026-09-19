<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3i1l743g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3i1l743g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fax" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn2zpo8ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn2zpo8ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cube-vertex" {...props}></Icon>

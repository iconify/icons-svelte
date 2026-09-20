<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgsr__boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hgsr__boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lift-gate-lowered" {...props}></Icon>

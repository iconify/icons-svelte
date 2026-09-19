<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-lmtub9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d-lmtub9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-down-stroke-12" {...props}></Icon>

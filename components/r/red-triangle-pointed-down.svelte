<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at6mhmmvf.css';
import '../../css/r/r258pibsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="at6mhmmvf"/><path class="r258pibsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-triangle-pointed-down" {...props}></Icon>

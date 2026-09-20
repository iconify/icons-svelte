<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2m5ub-n.css';
import '../../css/j/jmyubu8dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hv2m5ub-n"/><path class="jmyubu8dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:first-aid" {...props}></Icon>

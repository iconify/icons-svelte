<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usmo0gbrf.css';
import '../../css/t/tvepgg8ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="usmo0gbrf"/><path class="tvepgg8ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:right-arrow" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1aprlew.css';
import '../../css/l/l2uzblb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="rq1aprlew"/><path class="l2uzblb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:down-arrow" {...props}></Icon>

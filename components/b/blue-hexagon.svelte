<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbr_c7bzt.css';
import '../../css/x/x1mdp195q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fbr_c7bzt"/><path class="x1mdp195q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:blue-hexagon" {...props}></Icon>

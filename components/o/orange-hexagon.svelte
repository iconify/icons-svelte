<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4rlq3n0s.css';
import '../../css/x/x1mdp195q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="h4rlq3n0s"/><path class="x1mdp195q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orange-hexagon" {...props}></Icon>

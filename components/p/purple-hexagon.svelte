<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6h71cw6d.css';
import '../../css/x/x1mdp195q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="h6h71cw6d"/><path class="x1mdp195q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:purple-hexagon" {...props}></Icon>

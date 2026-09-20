<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnt4rgbuc.css';
import '../../css/x/x1mdp195q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xnt4rgbuc"/><path class="x1mdp195q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:brown-hexagon" {...props}></Icon>

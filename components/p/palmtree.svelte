<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_h132a_m.css';
import '../../css/f/fm754gtlz.css';
import '../../css/u/u9ev1ubbm.css';
import '../../css/b/b_-ksp75g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_h132a_m"/><path class="fm754gtlz"/><path class="u9ev1ubbm"/><path class="b_-ksp75g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:palmtree" {...props}></Icon>

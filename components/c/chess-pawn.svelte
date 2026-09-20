<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zqh6j4b-s.css';
import '../../css/d/d-o67lbcz.css';
import '../../css/x/x8q5aol2t.css';
import '../../css/j/j-o5shb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="zqh6j4b-s"/><path class="d-o67lbcz"/><path class="x8q5aol2t"/><path class="j-o5shb-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:chess-pawn" {...props}></Icon>

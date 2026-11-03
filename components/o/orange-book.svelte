<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8a-spftx.css';
import '../../css/f/f--a68y4g.css';
import '../../css/a/a8z3xdbuh.css';
import '../../css/j/jjuwgeb1s.css';
import '../../css/a/ay8131wny.css';
import '../../css/p/pvt39jcep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a8a-spftx"/><path class="f--a68y4g"/><path class="a8z3xdbuh"/><path class="jjuwgeb1s"/><circle class="ay8131wny"/><path class="pvt39jcep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orange-book" {...props}></Icon>

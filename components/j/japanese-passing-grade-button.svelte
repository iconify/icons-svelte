<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obi7p7-mc.css';
import '../../css/u/u38_ebckg.css';
import '../../css/m/my31-mbvu.css';
import '../../css/a/a6-44yfbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="obi7p7-mc"/><path class="u38_ebckg"/><path class="my31-mbvu"/><path class="a6-44yfbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:japanese-passing-grade-button" {...props}></Icon>

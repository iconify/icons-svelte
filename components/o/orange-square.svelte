<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx2r13bpi.css';
import '../../css/q/qy2vo7bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bx2r13bpi"/><path class="qy2vo7bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:orange-square" {...props}></Icon>

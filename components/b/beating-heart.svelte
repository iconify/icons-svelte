<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdsnylbwc.css';
import '../../css/l/lb80qlbob.css';
import '../../css/k/ko1bcvb2i.css';
import '../../css/c/ct87dwbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xdsnylbwc"/><g class="lb80qlbob"><path class="ko1bcvb2i"/><path class="ct87dwbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:beating-heart" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj104obcf.css';
import '../../css/v/vl1l4y1nm.css';
import '../../css/f/f0k7erb4e.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/v/v1xwazb_z.css';
import '../../css/f/feu_fzf4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<ellipse transform="rotate(-45 35.976 36.145)" class="zj104obcf"/><path class="vl1l4y1nm"/><path class="f0k7erb4e"/><g class="x8poo_bjf"><ellipse transform="rotate(-45 35.976 36.145)" class="v1xwazb_z"/><path class="feu_fzf4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:olive" {...props}></Icon>

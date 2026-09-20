<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnpejlbqu.css';
import '../../css/n/nipb_750s.css';
import '../../css/z/zrz8cqb2h.css';
import '../../css/g/gkdwti2oi.css';
import '../../css/g/gelbxrbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fnpejlbqu"/><path class="nipb_750s"/><path class="zrz8cqb2h"/><path class="gkdwti2oi"/><ellipse class="gelbxrbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ct-scan" {...props}></Icon>

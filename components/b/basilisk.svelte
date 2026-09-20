<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0l2_f2n.css';
import '../../css/o/oy_dogbda.css';
import '../../css/t/tvs8cjp-l.css';
import '../../css/a/ar4rr2hua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3310,"height":3310};
const content = `<g class="jy0l2_f2n"><circle class="oy_dogbda"/><ellipse class="tvs8cjp-l"/><path class="ar4rr2hua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:basilisk" {...props}></Icon>

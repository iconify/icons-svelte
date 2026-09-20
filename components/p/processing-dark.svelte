<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/q/q9u-cabmd.css';
import '../../css/w/wpcya1b_y.css';
import '../../css/q/qhgn009xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="q9u-cabmd"/><path class="wpcya1b_y"/><path class="qhgn009xs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:processing-dark" {...props}></Icon>

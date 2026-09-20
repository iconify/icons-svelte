<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/o/omqjj5lms.css';
import '../../css/i/itpmqb1vd.css';
import '../../css/l/lztqcuc6i.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path class="omqjj5lms"/><path clip-rule="evenodd" class="itpmqb1vd"/><path clip-rule="evenodd" class="lztqcuc6i"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:photo-camera-circle" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l0qtu8b-s.css';
import '../../css/a/ax9neccmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":189};
const content = `<g class="ft5dv1b6b"><path class="l0qtu8b-s"/><path class="ax9neccmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:pl" {...props}></Icon>

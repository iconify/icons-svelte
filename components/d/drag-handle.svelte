<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/dj8zxibgk.css';
import '../../css/g/gv0068sbg.css';
import '../../css/d/dv-gida4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="dj8zxibgk wm-shadow"/><path class="gv0068sbg wm-shadow"/><path class="dv-gida4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:drag-handle" {...props}></Icon>

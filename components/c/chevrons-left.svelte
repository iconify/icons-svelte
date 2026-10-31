<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/w1786d5mz.css';
import '../../css/w/wnbic79xe.css';
import '../../css/e/er7rs_byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="w1786d5mz wm-shadow"/><path class="wm-shadow wnbic79xe"/><path class="er7rs_byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chevrons-left" {...props}></Icon>

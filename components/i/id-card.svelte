<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/au6hhft4u.css';
import '../../css/g/gomb-26qh.css';
import '../../css/b/bf3uyq84n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="au6hhft4u wm-k"/><path class="gomb-26qh wm-shine"/><path class="bf3uyq84n wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:id-card" {...props}></Icon>

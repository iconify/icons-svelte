<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zv7kvd05e.css';
import '../../css/c/cpmjwca9p.css';
import '../../css/c/c9fy1mkgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zv7kvd05e"/><path class="cpmjwca9p"/><path class="c9fy1mkgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:ribbon-star" {...props}></Icon>

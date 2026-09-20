<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkmy5cc1h.css';
import '../../css/b/ba9_ej6ts.css';
import '../../css/z/z9o6zob5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkmy5cc1h"/><path class="ba9_ej6ts"/><path class="z9o6zob5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-right-square-duotone" {...props}></Icon>

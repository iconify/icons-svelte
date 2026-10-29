<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uh51hhbrp.css';
import '../../css/g/g489vwhdf.css';
import '../../css/o/ocoockb2g.css';
import '../../css/a/ax14dsbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uh51hhbrp"/><path class="g489vwhdf"/><path class="ocoockb2g"/><path class="ax14dsbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-duo" {...props}></Icon>

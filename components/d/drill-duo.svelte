<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eqyqj9bbr.css';
import '../../css/s/sg46neb7i.css';
import '../../css/m/m5u5l5b7g.css';
import '../../css/j/jrm8jlzgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="eqyqj9bbr"/><path class="sg46neb7i wm-a"/><path class="m5u5l5b7g wm-a"/><path class="jrm8jlzgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drill-duo" {...props}></Icon>

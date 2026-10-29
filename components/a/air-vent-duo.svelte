<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j1zl5-bua.css';
import '../../css/g/gn83_cb7i.css';
import '../../css/j/j1_apjast.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j1zl5-bua"/><path class="gn83_cb7i wm-a"/><path class="j1_apjast"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:air-vent-duo" {...props}></Icon>

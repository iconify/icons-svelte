<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bb7znibim.css';
import '../../css/b/b1z0d6brh.css';
import '../../css/i/ieced1b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bb7znibim"/><path class="b1z0d6brh"/><path class="ieced1b-r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:diya" {...props}></Icon>

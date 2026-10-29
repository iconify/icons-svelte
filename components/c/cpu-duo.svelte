<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b9xwaeb0f.css';
import '../../css/k/kx9parvdn.css';
import '../../css/v/vjsd4sbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b9xwaeb0f"/><path class="kx9parvdn wm-a"/><path class="vjsd4sbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cpu-duo" {...props}></Icon>

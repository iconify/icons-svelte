<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m403y6bez.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/k/k75npncbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m403y6bez secondary"/><g class="dt0cm9dhy primary"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="k75npncbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-heart-duo" {...props}></Icon>

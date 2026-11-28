<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/w/w56mytb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="w56mytb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-up" {...props}></Icon>

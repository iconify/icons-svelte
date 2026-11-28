<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bkhpw8bej.css';
import '../../css/i/izggtwq7w.css';
import '../../css/s/s2nwy5btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bkhpw8bej"/><path class="izggtwq7w"/><path class="s2nwy5btc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-x" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kg72hp23p.css';
import '../../css/r/rwu8qgbyp.css';
import '../../css/b/b86buo32x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kg72hp23p"/><path class="rwu8qgbyp wm-a"/><path class="b86buo32x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lock-duo" {...props}></Icon>

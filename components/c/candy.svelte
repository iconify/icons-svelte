<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lhi-d6nau.css';
import '../../css/f/fi474t81h.css';
import '../../css/x/xg17tff9f.css';
import '../../css/z/z8xzhab4p.css';
import '../../css/a/a6yvyhbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lhi-d6nau"/><path class="fi474t81h"/><path class="xg17tff9f"/><path class="z8xzhab4p"/><path class="a6yvyhbgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:candy" {...props}></Icon>

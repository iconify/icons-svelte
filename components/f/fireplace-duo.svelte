<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l9djeq8yk.css';
import '../../css/j/jrfoe58yb.css';
import '../../css/d/dg5kmnbiz.css';
import '../../css/p/pfodkzbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l9djeq8yk"/><path class="jrfoe58yb wm-a"/><path class="dg5kmnbiz wm-a"/><path class="pfodkzbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fireplace-duo" {...props}></Icon>

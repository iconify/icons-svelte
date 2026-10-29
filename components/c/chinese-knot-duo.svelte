<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yu2ay2bcw.css';
import '../../css/f/fv6d5gchd.css';
import '../../css/j/jam8cccqq.css';
import '../../css/w/w0-632-cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yu2ay2bcw"/><path class="fv6d5gchd wm-a"/><path class="jam8cccqq wm-a"/><path class="w0-632-cs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chinese-knot-duo" {...props}></Icon>

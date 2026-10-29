<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/joey29b2t.css';
import '../../css/m/m74-1jszs.css';
import '../../css/a/ao21d5blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="joey29b2t"/><path class="m74-1jszs wm-a"/><path class="ao21d5blb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-left-open-duo" {...props}></Icon>

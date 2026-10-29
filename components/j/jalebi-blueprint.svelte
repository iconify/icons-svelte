<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/njmk__s6q.css';
import '../../css/l/l33z8rc6h.css';
import '../../css/t/tjbxadb6s.css';
import '../../css/r/rd7sljvjm.css';
import '../../css/d/dgp8ihnse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="njmk__s6q wm-deco"/><path class="l33z8rc6h wm-deco"/><path class="tjbxadb6s wm-deco"/><path class="rd7sljvjm wm-k"/><path class="dgp8ihnse wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jalebi-blueprint" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zocsw-b9c.css';
import '../../css/a/albikqbom.css';
import '../../css/c/c7bj3u4fy.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zocsw-b9c"/><path class="albikqbom"/><path clip-rule="evenodd" class="c7bj3u4fy"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:radio-off" {...props}></Icon>

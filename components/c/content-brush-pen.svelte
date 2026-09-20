<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fro3_tw4w.css';
import '../../css/l/lfzgj2bpk.css';
import '../../css/f/fnorhmrao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fro3_tw4w"/><path class="lfzgj2bpk"/><path class="fnorhmrao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:content-brush-pen" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p0anpxbww.css';
import '../../css/r/rqco7omwy.css';
import '../../css/f/f_7mvhbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p0anpxbww"/><path class="rqco7omwy"/><path clip-rule="evenodd" class="f_7mvhbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-question-mark-outline" {...props}></Icon>

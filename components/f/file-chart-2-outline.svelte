<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kf2oy6bza.css';
import '../../css/j/jx8ve--2z.css';
import '../../css/h/h5wtxfm1n.css';
import '../../css/f/f_7mvhbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kf2oy6bza"/><path class="jx8ve--2z"/><path class="h5wtxfm1n"/><path clip-rule="evenodd" class="f_7mvhbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-chart-2-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kkh72vl5e.css';
import '../../css/i/ix1a3ybiw.css';
import '../../css/h/hve8fgbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kkh72vl5e"/><path class="ix1a3ybiw"/><path class="hve8fgbma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:eraser" {...props}></Icon>

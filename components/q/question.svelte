<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cwqybm13b.css';
import '../../css/w/wbdy8gb0y.css';
import '../../css/k/k4xam1b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwqybm13b"/><path class="wbdy8gb0y"/><path class="k4xam1b7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:question" {...props}></Icon>

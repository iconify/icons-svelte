<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g9409uhnn.css';
import '../../css/j/js1fb1lgb.css';
import '../../css/n/n1cw_vbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g9409uhnn"/><path clip-rule="evenodd" class="js1fb1lgb"/><path class="n1cw_vbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:dress" {...props}></Icon>

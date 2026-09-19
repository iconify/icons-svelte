<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r-pirlb1i.css';
import '../../css/c/ci9fsyyqx.css';
import '../../css/m/meco3rogb.css';
import '../../css/s/s29ll1g5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r-pirlb1i"/><path class="ci9fsyyqx"/><path class="meco3rogb"/><path class="s29ll1g5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud-down-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b3m1dxb1v.css';
import '../../css/a/aektm6bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b3m1dxb1v"/><path clip-rule="evenodd" class="aektm6bmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:exclamation-mark-triangle" {...props}></Icon>

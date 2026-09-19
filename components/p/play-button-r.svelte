<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bloafcben.css';
import '../../css/c/cu6hvibqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bloafcben"/><path class="cu6hvibqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-button-r" {...props}></Icon>

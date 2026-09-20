<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b4yvx5bqg.css';
import '../../css/q/qwt0l5e7j.css';
import '../../css/s/s-k-uwbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4yvx5bqg"/><path clip-rule="evenodd" class="qwt0l5e7j"/><path class="s-k-uwbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card2-filled" {...props}></Icon>

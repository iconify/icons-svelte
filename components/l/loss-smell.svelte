<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/glmqoxo2g.css';
import '../../css/t/tgi27dstf.css';
import '../../css/b/bs4c_4bsg.css';
import '../../css/q/q8p-vyb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="glmqoxo2g"/><path class="tgi27dstf"/><path clip-rule="evenodd" class="bs4c_4bsg"/><path class="q8p-vyb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:loss-smell" {...props}></Icon>

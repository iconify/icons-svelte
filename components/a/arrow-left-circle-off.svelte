<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bix5dccyb.css';
import '../../css/u/ue-8cqbhf.css';
import '../../css/w/wsd75ceda.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bix5dccyb"/><path clip-rule="evenodd" class="ue-8cqbhf"/><path clip-rule="evenodd" class="wsd75ceda"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:arrow-left-circle-off" {...props}></Icon>

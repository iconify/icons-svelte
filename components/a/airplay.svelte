<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/h/hox00fw-n.css';
import '../../css/v/vb569dqcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="hox00fw-n"/><path class="vb569dqcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:airplay" {...props}></Icon>

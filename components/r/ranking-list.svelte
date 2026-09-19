<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/v/vp8jg4bpk.css';
import '../../css/z/zotbml7et.css';
import '../../css/v/vuq5iub0q.css';
import '../../css/i/i3e4kwb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="vp8jg4bpk"/><path class="zotbml7et"/><path class="vuq5iub0q"/><path class="i3e4kwb2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:ranking-list" {...props}></Icon>

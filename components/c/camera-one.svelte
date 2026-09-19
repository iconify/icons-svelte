<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/y/yez7skblq.css';
import '../../css/z/zh_bpuben.css';
import '../../css/h/h2uo0wbmx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMRzgUPhe"><g class="aql7dnt-u"><circle class="yez7skblq"/><circle class="zh_bpuben"/><path class="h2uo0wbmx"/></g></mask></defs><path mask="url(#SVGMRzgUPhe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:camera-one" {...props}></Icon>

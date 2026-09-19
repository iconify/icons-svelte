<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/y/y2dgydb7o.css';
import '../../css/a/a2im80b3m.css';
import '../../css/g/gj5isf39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="y2dgydb7o"/><path class="a2im80b3m"/><path class="gj5isf39e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:afferent-two" {...props}></Icon>

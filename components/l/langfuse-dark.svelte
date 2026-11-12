<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfqg2gjhk.css';
import '../../css/z/zq-xd4b2s.css';
import '../../css/x/xv20pn3tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dfqg2gjhk"/><path class="zq-xd4b2s"/><path class="xv20pn3tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:langfuse-dark" {...props}></Icon>

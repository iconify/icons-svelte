<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ttwubdw.css';
import '../../css/v/vxrrplwnx.css';
import '../../css/b/bwdyegfbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-ttwubdw"/><path class="vxrrplwnx"/><path class="bwdyegfbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marp-dark" {...props}></Icon>

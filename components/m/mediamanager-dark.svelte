<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxxptl7ss.css';
import '../../css/x/xzdvdubue.css';
import '../../css/c/cmmtxw9or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxxptl7ss"/><path class="xzdvdubue"/><path class="cmmtxw9or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamanager-dark" {...props}></Icon>

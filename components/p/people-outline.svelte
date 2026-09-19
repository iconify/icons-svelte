<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnfili8xo.css';
import '../../css/n/nnly1dl6q.css';
import '../../css/p/p2ysx8bbc.css';
import '../../css/z/zbo3cxv1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnfili8xo"/><path class="nnly1dl6q"/><path class="p2ysx8bbc"/><path class="zbo3cxv1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:people-outline" {...props}></Icon>

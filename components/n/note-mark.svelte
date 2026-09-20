<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsxw_objg.css';
import '../../css/g/g2hg1_bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsxw_objg"/><path class="g2hg1_bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:note-mark" {...props}></Icon>

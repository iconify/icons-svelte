<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrk_i1wgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrk_i1wgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:redo-circle-square-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwit5_4bm.css';
import '../../css/z/z75ed3b-u.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/j/jdz4f3gnm.css';
import '../../css/z/zul9ixm_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwit5_4bm"/><path class="z75ed3b-u"/><g class="xtpeb-edw"><path class="jdz4f3gnm"/><path class="zul9ixm_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-roller-bold-duotone" {...props}></Icon>

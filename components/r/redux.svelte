<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99j2sggn.css';
import '../../css/r/rswgeacvu.css';
import '../../css/z/zidxczbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t99j2sggn"/><path class="rswgeacvu"/><path class="zidxczbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:redux" {...props}></Icon>

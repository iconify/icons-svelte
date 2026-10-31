<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wta7eoblc.css';
import '../../css/u/u442ulstg.css';
import '../../css/i/ieawaobjk.css';
import '../../css/j/ju2ksxgoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wta7eoblc"/><path class="u442ulstg"/><path class="ieawaobjk"/><path class="ju2ksxgoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:east-timor" {...props}></Icon>

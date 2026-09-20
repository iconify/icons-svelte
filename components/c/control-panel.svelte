<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qivazt3xq.css';
import '../../css/h/hwkz_mbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qivazt3xq"/><path class="hwkz_mbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:control-panel" {...props}></Icon>

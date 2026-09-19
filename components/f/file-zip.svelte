<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xunbskfrx.css';
import '../../css/t/t756e-aqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xunbskfrx"/><path class="t756e-aqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-zip" {...props}></Icon>

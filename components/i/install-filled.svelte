<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp53h7iuv.css';
import '../../css/c/cs02177wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp53h7iuv"/><path class="cs02177wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bms_014rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bms_014rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chinese-cabbage-filled" {...props}></Icon>

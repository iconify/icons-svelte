<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvtnscbtx.css';
import '../../css/y/yzo5plbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vvtnscbtx"/><circle class="yzo5plbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:live" {...props}></Icon>

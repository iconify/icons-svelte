<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh65wbcob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh65wbcob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-line" {...props}></Icon>

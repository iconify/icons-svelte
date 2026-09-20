<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yurwjibje.css';
import '../../css/v/vqsj2lnqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yurwjibje"/><path class="vqsj2lnqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-workflow-merge-2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyd83wisg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyd83wisg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:file-x" {...props}></Icon>

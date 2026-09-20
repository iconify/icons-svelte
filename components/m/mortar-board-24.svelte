<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysl3ccail.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysl3ccail"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mortar-board-24" {...props}></Icon>

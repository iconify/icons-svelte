<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uforufbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uforufbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-horizontal" {...props}></Icon>

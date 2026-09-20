<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnjzijbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnjzijbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:empty-box-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exnl6nbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exnl6nbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-check-line" {...props}></Icon>

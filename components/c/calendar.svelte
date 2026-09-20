<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qem7g_bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qem7g_bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:calendar" {...props}></Icon>

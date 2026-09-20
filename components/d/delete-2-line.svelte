<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb-s0g_vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb-s0g_vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-2-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgngm0alo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgngm0alo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-dot-right-horizontal-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnt3u0v0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnt3u0v0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grip-horizontal" {...props}></Icon>

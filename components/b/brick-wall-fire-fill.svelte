<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oti0a6g5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oti0a6g5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brick-wall-fire-fill" {...props}></Icon>

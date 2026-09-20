<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw_1dxbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw_1dxbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-vertical-line" {...props}></Icon>

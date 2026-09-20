<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8cxkwbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8cxkwbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-line" {...props}></Icon>

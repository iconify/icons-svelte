<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjym-4_wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjym-4_wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:audio-lines-x" {...props}></Icon>

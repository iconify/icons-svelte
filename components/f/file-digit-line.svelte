<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv8fou2-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv8fou2-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-digit-line" {...props}></Icon>

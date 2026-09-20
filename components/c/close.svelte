<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi__8e8vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="fi__8e8vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:close" {...props}></Icon>

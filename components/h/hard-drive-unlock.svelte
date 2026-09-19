<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx0dpu8wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zx0dpu8wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hard-drive-unlock" {...props}></Icon>

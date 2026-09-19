<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf10fbbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="zf10fbbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pencil-square" {...props}></Icon>

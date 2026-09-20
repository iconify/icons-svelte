<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz4ck4-4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rz4ck4-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flush-curb-with-question-mark" {...props}></Icon>

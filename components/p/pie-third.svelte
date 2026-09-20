<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkiz0wbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="qkiz0wbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pie-third" {...props}></Icon>

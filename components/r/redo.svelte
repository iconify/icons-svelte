<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yosfa9p7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yosfa9p7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:redo" {...props}></Icon>

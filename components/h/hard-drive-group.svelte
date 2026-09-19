<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi28gi9tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fi28gi9tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hard-drive-group" {...props}></Icon>

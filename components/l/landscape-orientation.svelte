<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls3v0ebdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ls3v0ebdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:landscape-orientation" {...props}></Icon>

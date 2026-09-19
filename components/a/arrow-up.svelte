<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn7avwbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":630,"height":700};
const content = `<path class="zn7avwbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:arrow-up" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1ipy5m-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j1ipy5m-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:help-mirrored" {...props}></Icon>

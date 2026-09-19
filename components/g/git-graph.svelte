<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc64bdcbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wc64bdcbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:git-graph" {...props}></Icon>

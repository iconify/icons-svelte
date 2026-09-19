<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nshr6y52x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nshr6y52x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:deciduous-tree" {...props}></Icon>

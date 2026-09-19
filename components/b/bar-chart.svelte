<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oifsxdbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oifsxdbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bar-chart" {...props}></Icon>

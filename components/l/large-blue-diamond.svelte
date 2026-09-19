<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tni516bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tni516bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:large-blue-diamond" {...props}></Icon>

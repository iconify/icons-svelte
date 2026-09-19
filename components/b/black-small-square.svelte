<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aicxeqb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aicxeqb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-small-square" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj4qn8git.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wj4qn8git"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:rightwards-hand" {...props}></Icon>

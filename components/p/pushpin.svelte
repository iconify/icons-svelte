<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0wc9d6ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e0wc9d6ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pushpin" {...props}></Icon>

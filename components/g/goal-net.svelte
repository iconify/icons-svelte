<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8nupmb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e8nupmb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:goal-net" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9gmnzaks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o9gmnzaks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:broom" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4df0dbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h4df0dbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:large-orange-diamond" {...props}></Icon>

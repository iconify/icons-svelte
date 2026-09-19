<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4ww4zb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4ww4zb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-triangle" {...props}></Icon>

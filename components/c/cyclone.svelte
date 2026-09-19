<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uannv650s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uannv650s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cyclone" {...props}></Icon>

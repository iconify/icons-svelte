<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euzqdr04x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="euzqdr04x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:index-pointing-up" {...props}></Icon>

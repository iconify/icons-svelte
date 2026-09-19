<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxu8d89-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nxu8d89-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:baseball" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3k9iwbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e3k9iwbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:roller-coaster" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ios_9nm3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ios_9nm3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:lotus" {...props}></Icon>

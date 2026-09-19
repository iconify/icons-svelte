<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av32gzy1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="av32gzy1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:left-speech-bubble" {...props}></Icon>

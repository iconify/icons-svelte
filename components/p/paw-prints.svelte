<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anea1nyir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="anea1nyir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:paw-prints" {...props}></Icon>

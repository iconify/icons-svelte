<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9pftxwov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z9pftxwov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hollow-red-circle" {...props}></Icon>

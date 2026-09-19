<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8sg9szmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i8sg9szmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-tentative-mirrored" {...props}></Icon>

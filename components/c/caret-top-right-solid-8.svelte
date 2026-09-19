<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhoz3sbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hhoz3sbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-top-right-solid-8" {...props}></Icon>

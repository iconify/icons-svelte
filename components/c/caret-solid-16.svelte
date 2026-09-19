<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djs755xxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="djs755xxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-solid-16" {...props}></Icon>

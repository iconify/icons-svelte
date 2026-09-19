<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-7dubgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gb-7dubgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-top-left-solid-8" {...props}></Icon>

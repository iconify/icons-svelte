<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8u4d0zwp.css';
import '../../css/m/ms064kbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i8u4d0zwp"/><path class="ms064kbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:map-boundary" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op8lguefd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="op8lguefd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:linux-logo-32" {...props}></Icon>

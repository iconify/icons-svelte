<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7qjasj9f.css';
import '../../css/y/y8x22khvr.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l7qjasj9f"/><path class="y8x22khvr"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-check-20-bold" {...props}></Icon>

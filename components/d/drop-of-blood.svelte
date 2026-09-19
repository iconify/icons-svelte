<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz5c7gbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pz5c7gbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:drop-of-blood" {...props}></Icon>

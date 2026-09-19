<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de2nv-xgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="de2nv-xgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cloud-with-snow" {...props}></Icon>

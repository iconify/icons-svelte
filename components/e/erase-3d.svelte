<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5r_4793o.css';
import '../../css/k/kgwqmdg7m.css';
import '../../css/y/y8b389s9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5r_4793o"/><path class="kgwqmdg7m"/><path class="y8b389s9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:erase-3d" {...props}></Icon>

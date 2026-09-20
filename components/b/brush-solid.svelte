<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i82r32b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i82r32b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:brush-solid" {...props}></Icon>

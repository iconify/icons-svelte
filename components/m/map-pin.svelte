<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9p0trbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i9p0trbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:map-pin" {...props}></Icon>

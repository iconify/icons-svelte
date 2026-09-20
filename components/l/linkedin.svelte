<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_xbgeb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_xbgeb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:linkedin" {...props}></Icon>

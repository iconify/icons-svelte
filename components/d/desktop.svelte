<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0l4dp1jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0l4dp1jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:desktop" {...props}></Icon>

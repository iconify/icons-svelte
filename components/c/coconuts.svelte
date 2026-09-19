<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy-n0abja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yy-n0abja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coconuts" {...props}></Icon>

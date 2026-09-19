<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyy0yv7dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyy0yv7dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:captions" {...props}></Icon>

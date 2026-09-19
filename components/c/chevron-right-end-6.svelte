<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-6j3fb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w-6j3fb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-right-end-6" {...props}></Icon>

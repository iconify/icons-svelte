<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlxh2hoir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wlxh2hoir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:paperclip" {...props}></Icon>

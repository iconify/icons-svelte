<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6s0e3buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6s0e3buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paperclip" {...props}></Icon>

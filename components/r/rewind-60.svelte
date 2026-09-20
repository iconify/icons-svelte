<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1c0ct14k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1c0ct14k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rewind-60" {...props}></Icon>

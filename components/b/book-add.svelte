<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwhuy2b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwhuy2b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-add" {...props}></Icon>

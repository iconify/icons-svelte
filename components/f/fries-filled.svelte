<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi8xxdwkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi8xxdwkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fries-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t32xobc5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t32xobc5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:band-aid" {...props}></Icon>

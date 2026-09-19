<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry3so7gim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry3so7gim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location" {...props}></Icon>

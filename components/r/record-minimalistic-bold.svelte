<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upuz4ypky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upuz4ypky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-minimalistic-bold" {...props}></Icon>

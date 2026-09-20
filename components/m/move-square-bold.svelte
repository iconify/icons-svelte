<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joa8-ubia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="joa8-ubia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-square-bold" {...props}></Icon>

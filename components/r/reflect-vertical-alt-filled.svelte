<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne5zp8bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne5zp8bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reflect-vertical-alt-filled" {...props}></Icon>

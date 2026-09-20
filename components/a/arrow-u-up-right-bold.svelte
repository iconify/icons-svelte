<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylpowi0yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylpowi0yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-up-right-bold" {...props}></Icon>

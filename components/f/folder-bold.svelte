<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ds70btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ds70btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-bold" {...props}></Icon>

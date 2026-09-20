<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgb52ccwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgb52ccwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:new-folder-flat" {...props}></Icon>

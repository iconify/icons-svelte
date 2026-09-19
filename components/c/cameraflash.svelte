<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcncdub3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="tcncdub3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cameraflash" {...props}></Icon>

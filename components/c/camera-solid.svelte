<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jso1dfb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jso1dfb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:camera-solid" {...props}></Icon>

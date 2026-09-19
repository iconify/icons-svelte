<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqwrgzbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":737,"height":646};
const content = `<path class="wqwrgzbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:camera" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsob5cjch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsob5cjch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-lens-line" {...props}></Icon>

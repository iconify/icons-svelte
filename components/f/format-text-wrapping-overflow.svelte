<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6ckcpbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6ckcpbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-wrapping-overflow" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hez8wsb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hez8wsb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:battery-low-line" {...props}></Icon>

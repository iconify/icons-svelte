<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo71ltb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo71ltb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-automotive-line" {...props}></Icon>

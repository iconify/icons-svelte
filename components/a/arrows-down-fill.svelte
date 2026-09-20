<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3rk9hrsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3rk9hrsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-down-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cswyp5p5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cswyp5p5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-multiple" {...props}></Icon>

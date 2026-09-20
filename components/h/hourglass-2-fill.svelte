<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j62-f-ylc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j62-f-ylc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hourglass-2-fill" {...props}></Icon>

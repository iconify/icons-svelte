<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8_9pzbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8_9pzbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fi" {...props}></Icon>

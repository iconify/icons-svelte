<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w11ibabcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w11ibabcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dumbbell2-filled" {...props}></Icon>

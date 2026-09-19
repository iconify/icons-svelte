<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm4hri4ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4hri4ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:notes" {...props}></Icon>

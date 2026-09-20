<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twrtzr8ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="twrtzr8ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:airfield-15" {...props}></Icon>

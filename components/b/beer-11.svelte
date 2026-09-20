<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6wa-bbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="h6wa-bbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:beer-11" {...props}></Icon>

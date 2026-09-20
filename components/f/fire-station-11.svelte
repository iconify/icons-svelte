<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8f-lov2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="t8f-lov2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fire-station-11" {...props}></Icon>

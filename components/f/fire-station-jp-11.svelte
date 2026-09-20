<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgk16pb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="mgk16pb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fire-station-jp-11" {...props}></Icon>

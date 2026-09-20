<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw1ocebmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="cw1ocebmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:pharmacy-11" {...props}></Icon>

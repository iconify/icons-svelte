<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6hc3d11b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="t6hc3d11b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:college-jp-11" {...props}></Icon>

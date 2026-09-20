<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-w0bb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wk-w0bb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:0" {...props}></Icon>

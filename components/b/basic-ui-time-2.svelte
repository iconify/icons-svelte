<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfuhywbmz.css';
import '../../css/c/ckv8-4w9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jfuhywbmz"/><path clip-rule="evenodd" class="ckv8-4w9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-time-2" {...props}></Icon>

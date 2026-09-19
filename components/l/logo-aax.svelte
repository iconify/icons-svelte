<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vly4rr3ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vly4rr3ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-aax" {...props}></Icon>

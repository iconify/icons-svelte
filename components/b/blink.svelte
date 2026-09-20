<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfyllwbid.css';
import '../../css/y/yklxlcb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hfyllwbid"/><path class="yklxlcb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:blink" {...props}></Icon>

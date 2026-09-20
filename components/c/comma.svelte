<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0oghdcwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v0oghdcwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:comma" {...props}></Icon>

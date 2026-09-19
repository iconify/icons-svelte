<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy5-_ebch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="sy5-_ebch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:removetags" {...props}></Icon>

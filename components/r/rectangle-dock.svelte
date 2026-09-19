<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziprlc7ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ziprlc7ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-dock" {...props}></Icon>

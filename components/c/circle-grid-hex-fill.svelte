<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j26yc11gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j26yc11gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:circle-grid-hex-fill" {...props}></Icon>

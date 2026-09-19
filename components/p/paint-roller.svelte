<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd7g7_byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd7g7_byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:paint-roller" {...props}></Icon>

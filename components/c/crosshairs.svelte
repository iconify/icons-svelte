<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmpyq4bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wmpyq4bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:crosshairs" {...props}></Icon>

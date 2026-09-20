<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuh36-brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wuh36-brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-grab" {...props}></Icon>

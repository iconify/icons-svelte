<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4mdfm72f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f4mdfm72f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-i" {...props}></Icon>

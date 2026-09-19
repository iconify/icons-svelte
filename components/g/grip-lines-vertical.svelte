<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj2cj9b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="jj2cj9b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grip-lines-vertical" {...props}></Icon>

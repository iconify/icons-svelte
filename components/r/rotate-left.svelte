<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsl99zbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsl99zbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rotate-left" {...props}></Icon>

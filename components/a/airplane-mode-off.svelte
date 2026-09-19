<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6q3qci0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6q3qci0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:airplane-mode-off" {...props}></Icon>

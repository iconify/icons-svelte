<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8gd8obtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p8gd8obtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notepad-text" {...props}></Icon>

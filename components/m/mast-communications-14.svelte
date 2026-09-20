<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs4ystbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qs4ystbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:mast-communications-14" {...props}></Icon>

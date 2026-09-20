<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px7vqjbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="px7vqjbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:party-popper" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-r2acsdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z-r2acsdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:earth-airplane-remix" {...props}></Icon>

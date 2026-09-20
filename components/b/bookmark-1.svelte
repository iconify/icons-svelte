<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxiozebjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="bxiozebjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bookmark-1" {...props}></Icon>

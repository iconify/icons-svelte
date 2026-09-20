<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9znblbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x9znblbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-top-left-bottom-right-bottom-left-top-right" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x45dlkbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x45dlkbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-book" {...props}></Icon>

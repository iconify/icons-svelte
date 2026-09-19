<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1uvyt01z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="x1uvyt01z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:box-open" {...props}></Icon>

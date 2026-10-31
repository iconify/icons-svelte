<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz70ulbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fz70ulbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-book-in-eaved-gabled-building" {...props}></Icon>

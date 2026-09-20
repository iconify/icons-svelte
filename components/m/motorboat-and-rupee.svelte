<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i106bb_zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i106bb_zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-rupee" {...props}></Icon>

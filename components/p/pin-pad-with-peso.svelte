<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enm4i5bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="enm4i5bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-peso" {...props}></Icon>

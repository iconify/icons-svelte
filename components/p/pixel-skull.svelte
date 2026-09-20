<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkhsd8blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lkhsd8blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-skull" {...props}></Icon>

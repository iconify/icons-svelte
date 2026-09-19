<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-fh5kbgy.css';
import '../../css/n/nw5k1bbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x-fh5kbgy"/><path class="nw5k1bbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-list-stroke-12" {...props}></Icon>

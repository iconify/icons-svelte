<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkan-9bwk.css';
import '../../css/l/l307u0bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dkan-9bwk"/><path class="l307u0bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pricetags" {...props}></Icon>

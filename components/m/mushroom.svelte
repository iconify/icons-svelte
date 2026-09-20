<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyefmbdcw.css';
import '../../css/f/fc0n3k16d.css';
import '../../css/u/utv6qqbkb.css';
import '../../css/w/whkqkbbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cyefmbdcw"/><circle class="fc0n3k16d"/><circle class="utv6qqbkb"/><circle class="whkqkbbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mushroom" {...props}></Icon>

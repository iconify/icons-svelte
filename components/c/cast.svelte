<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tquyp2c9p.css';
import '../../css/f/fd9f55byh.css';
import '../../css/c/cui1j9-yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tquyp2c9p"/><path class="fd9f55byh"/><path class="cui1j9-yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cast" {...props}></Icon>

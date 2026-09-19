<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cclncg_2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cclncg_2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:exchange-alt" {...props}></Icon>

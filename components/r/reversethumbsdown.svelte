<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de91r55gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de91r55gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:reversethumbsdown" {...props}></Icon>

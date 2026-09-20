<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wly3hnkvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wly3hnkvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:call" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdeo76mkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pdeo76mkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-round-down" {...props}></Icon>

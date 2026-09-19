<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gtywbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="u7gtywbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:balance-wallet" {...props}></Icon>

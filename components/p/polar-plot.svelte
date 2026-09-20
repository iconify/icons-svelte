<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtery-rhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtery-rhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:polar-plot" {...props}></Icon>

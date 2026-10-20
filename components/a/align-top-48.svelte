<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjtwhsb_o.css';
import '../../css/x/xg42qpbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fjtwhsb_o"/><path class="xg42qpbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-top-48" {...props}></Icon>

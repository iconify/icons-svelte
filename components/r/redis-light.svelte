<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynl1j0b_y.css';
import '../../css/s/s8or9-btt.css';
import '../../css/l/ln9fce54w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ynl1j0b_y"/><path class="s8or9-btt"/><path class="ln9fce54w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redis-light" {...props}></Icon>

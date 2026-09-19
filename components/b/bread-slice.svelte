<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uab_dab1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uab_dab1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bread-slice" {...props}></Icon>

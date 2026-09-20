<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edhc3zbwf.css';
import '../../css/p/pdtt5t4xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edhc3zbwf"/><path class="pdtt5t4xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:here-now" {...props}></Icon>

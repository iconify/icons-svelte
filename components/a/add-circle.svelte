<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ntt5bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3ntt5bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-circle" {...props}></Icon>

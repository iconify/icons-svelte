<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-1oz4bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s-1oz4bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cashier" {...props}></Icon>

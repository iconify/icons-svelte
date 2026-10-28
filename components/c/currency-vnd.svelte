<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf0p-ybka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0p-ybka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-vnd" {...props}></Icon>

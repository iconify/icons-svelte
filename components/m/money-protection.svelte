<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfb0ibcol.css';
import '../../css/m/m1m99qwsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lfb0ibcol"/><path class="m1m99qwsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:money-protection" {...props}></Icon>

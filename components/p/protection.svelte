<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfb0ibcol.css';
import '../../css/o/oov6ojd_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lfb0ibcol"/><path class="oov6ojd_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:protection" {...props}></Icon>

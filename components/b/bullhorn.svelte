<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6fxp_bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w6fxp_bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bullhorn" {...props}></Icon>

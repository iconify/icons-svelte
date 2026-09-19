<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_tdmcb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":424};
const content = `<path class="u_tdmcb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-recline-normal" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhnrx_bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhnrx_bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-left" {...props}></Icon>

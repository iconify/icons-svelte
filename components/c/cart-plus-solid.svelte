<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufp1axb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufp1axb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cart-plus-solid" {...props}></Icon>

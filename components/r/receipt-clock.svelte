<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4k0wyb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4k0wyb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:receipt-clock" {...props}></Icon>

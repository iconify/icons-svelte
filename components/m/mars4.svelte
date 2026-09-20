<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sku-uqfty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sku-uqfty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mars4" {...props}></Icon>

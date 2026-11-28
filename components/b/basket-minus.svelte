<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll162-brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll162-brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket-minus" {...props}></Icon>

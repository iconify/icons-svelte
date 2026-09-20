<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfas3bcyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lfas3bcyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cart-full" {...props}></Icon>

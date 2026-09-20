<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc-6m5bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vc-6m5bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cart-minus-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmwu8mbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmwu8mbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-payment-card-in-slot" {...props}></Icon>

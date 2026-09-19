<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e90cm3b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e90cm3b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pricing-quick-proposal" {...props}></Icon>

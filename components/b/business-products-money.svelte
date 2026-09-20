<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ns15bcg.css';
import '../../css/l/lgj5z1bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n9ns15bcg"/><path class="lgj5z1bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-money" {...props}></Icon>

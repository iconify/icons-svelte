<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8hlz4bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8hlz4bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-cart-48" {...props}></Icon>

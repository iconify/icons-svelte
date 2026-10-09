<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez1ledqsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ez1ledqsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-cart-48-bold" {...props}></Icon>

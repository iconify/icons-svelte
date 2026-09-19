<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uge65rbva.css';
import '../../css/p/pq7bzbb4c.css';
import '../../css/e/e-neq9bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uge65rbva"/><path class="pq7bzbb4c"/><path class="e-neq9bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cart-outline" {...props}></Icon>

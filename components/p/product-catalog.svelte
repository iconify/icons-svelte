<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8018i56a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8018i56a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:product-catalog" {...props}></Icon>

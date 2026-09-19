<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as1l3gb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="as1l3gb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cart-plus" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moat_y9bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="moat_y9bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-1-wave" {...props}></Icon>

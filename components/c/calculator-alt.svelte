<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv_nh4bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uv_nh4bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calculator-alt" {...props}></Icon>

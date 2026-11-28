<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp_kx_kzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_kx_kzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:piggy-bank-check" {...props}></Icon>

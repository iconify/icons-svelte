<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgm_f_m2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lgm_f_m2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:link-chain-solid" {...props}></Icon>

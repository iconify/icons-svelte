<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc5k0_b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc5k0_b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:molotovtv" {...props}></Icon>

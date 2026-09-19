<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzmvx9hyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzmvx9hyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:faucet" {...props}></Icon>

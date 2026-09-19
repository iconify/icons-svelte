<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0m-ghb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="l0m-ghb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-moon-rain" {...props}></Icon>

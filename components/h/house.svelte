<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_ay6dcrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="a_ay6dcrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house" {...props}></Icon>

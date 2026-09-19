<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr5ki4baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xr5ki4baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:light-bulb-20-solid" {...props}></Icon>

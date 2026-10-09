<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv89jg_sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uv89jg_sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-footprint-20" {...props}></Icon>

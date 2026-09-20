<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv9xr--ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv9xr--ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mikrotik" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn5it8i0p.css';
import '../../css/a/az2bjjb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn5it8i0p"/><path class="az2bjjb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dotenvx" {...props}></Icon>

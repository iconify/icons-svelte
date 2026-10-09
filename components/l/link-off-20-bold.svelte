<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn_u8juie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gn_u8juie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-off-20-bold" {...props}></Icon>

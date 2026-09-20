<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upz5ji1nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upz5ji1nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:list-layout-outline" {...props}></Icon>

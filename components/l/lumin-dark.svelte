<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_crs_o9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":59,"height":59,"left":582,"top":232.67};
const content = `<path class="s_crs_o9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lumin-dark" {...props}></Icon>

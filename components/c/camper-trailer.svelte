<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy_tt7b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gy_tt7b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:camper-trailer" {...props}></Icon>

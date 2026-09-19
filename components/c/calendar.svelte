<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuzco_fmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="tuzco_fmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:calendar" {...props}></Icon>

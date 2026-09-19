<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa_p6gi4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="fa_p6gi4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-net-o" {...props}></Icon>

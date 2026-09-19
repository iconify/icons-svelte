<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo8lcs_8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uo8lcs_8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-battery-charging" {...props}></Icon>

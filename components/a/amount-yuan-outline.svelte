<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_8_z1bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s_8_z1bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-yuan-outline" {...props}></Icon>

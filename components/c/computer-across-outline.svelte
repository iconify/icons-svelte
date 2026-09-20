<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcqxiub3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vcqxiub3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:computer-across-outline" {...props}></Icon>

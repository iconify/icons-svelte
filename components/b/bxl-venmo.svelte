<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd2vfeb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd2vfeb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-venmo" {...props}></Icon>

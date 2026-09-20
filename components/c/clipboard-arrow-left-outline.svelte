<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_j3_ybsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_j3_ybsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-arrow-left-outline" {...props}></Icon>

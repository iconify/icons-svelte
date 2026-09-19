<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_v5q8_hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_v5q8_hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:house-solar-panel" {...props}></Icon>

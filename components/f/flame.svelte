<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_6_m30m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4_6_m30m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flame" {...props}></Icon>

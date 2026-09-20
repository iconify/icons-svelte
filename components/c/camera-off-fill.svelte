<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_nhuabjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_nhuabjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-off-fill" {...props}></Icon>

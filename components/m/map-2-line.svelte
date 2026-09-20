<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_2pd5bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2pd5bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-2-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuabpnbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuabpnbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-down-long-fill" {...props}></Icon>

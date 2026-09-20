<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0c0eu8vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0c0eu8vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pipe-wrench" {...props}></Icon>

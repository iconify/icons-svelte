<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz80s5bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz80s5bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnet-linear" {...props}></Icon>

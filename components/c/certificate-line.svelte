<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpno97b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpno97b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:certificate-line" {...props}></Icon>

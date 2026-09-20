<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lponrlbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lponrlbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:music-on-off-1-bold" {...props}></Icon>

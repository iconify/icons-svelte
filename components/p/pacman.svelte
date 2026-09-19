<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqnu7xbid.css';
import '../../css/f/fw-cofgvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqnu7xbid"/><path class="fw-cofgvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pacman" {...props}></Icon>

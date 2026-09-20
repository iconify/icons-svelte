<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq8vqkbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq8vqkbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:device-desktop" {...props}></Icon>

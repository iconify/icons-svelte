<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxab3-b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxab3-b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bars-3-bottom-center-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy2pjbcso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy2pjbcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-diamond-multiple-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xomp7-b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xomp7-b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:behance" {...props}></Icon>

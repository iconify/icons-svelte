<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wne1pacex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wne1pacex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:clock-fading" {...props}></Icon>

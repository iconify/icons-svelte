<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wot1xhjvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wot1xhjvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:block-game" {...props}></Icon>

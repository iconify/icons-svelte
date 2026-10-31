<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p98urxskq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p98urxskq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-play-fill-round" {...props}></Icon>

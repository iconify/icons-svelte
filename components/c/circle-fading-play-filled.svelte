<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkjmfib4i.css';
import '../../css/s/s2r542g-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkjmfib4i"/><path class="s2r542g-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-fading-play-filled" {...props}></Icon>

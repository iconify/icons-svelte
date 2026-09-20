<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh7l6ubcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh7l6ubcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playlist-line" {...props}></Icon>

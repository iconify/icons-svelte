<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcgn157ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcgn157ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:codepen" {...props}></Icon>

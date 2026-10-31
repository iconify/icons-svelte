<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/towhhu73f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="towhhu73f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:behance-fill-round" {...props}></Icon>

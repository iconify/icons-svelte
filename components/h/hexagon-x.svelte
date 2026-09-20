<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9l4y-1ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9l4y-1ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-x" {...props}></Icon>

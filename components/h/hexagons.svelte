<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a32w6l6cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a32w6l6cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagons" {...props}></Icon>

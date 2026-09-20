<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a82up1x0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a82up1x0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-r-filled" {...props}></Icon>

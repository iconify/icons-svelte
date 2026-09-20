<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1p3sacgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1p3sacgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-plus-2" {...props}></Icon>

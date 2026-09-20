<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujuhc5bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujuhc5bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:intersect-line" {...props}></Icon>

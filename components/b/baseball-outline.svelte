<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3-q4cbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3-q4cbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baseball-outline" {...props}></Icon>

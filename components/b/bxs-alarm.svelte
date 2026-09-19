<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rejenib5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rejenib5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-alarm" {...props}></Icon>

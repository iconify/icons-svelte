<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruo-o8h7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruo-o8h7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podcast-play" {...props}></Icon>
